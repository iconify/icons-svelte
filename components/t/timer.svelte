<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s83reacla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="s83reacla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:timer" {...props}></Icon>
