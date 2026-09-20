<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3_5tnbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="f3_5tnbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-outline" {...props}></Icon>
