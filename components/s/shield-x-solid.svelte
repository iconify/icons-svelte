<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0jgelb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="e0jgelb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:shield-x-solid" {...props}></Icon>
