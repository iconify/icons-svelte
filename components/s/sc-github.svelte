<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oexiugx6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path clip-rule="evenodd" class="oexiugx6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:sc-github" {...props}></Icon>
