<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7wyjebmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="b7wyjebmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:stack" {...props}></Icon>
