<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idf471b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="idf471b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:stop" {...props}></Icon>
