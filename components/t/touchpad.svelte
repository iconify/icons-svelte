<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dczarkgib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":896};
const content = `<path class="dczarkgib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:touchpad" {...props}></Icon>
