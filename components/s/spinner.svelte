<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu7p_-bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hu7p_-bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:spinner" {...props}></Icon>
