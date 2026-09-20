<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc8tembil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc8tembil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-settings-line" {...props}></Icon>
