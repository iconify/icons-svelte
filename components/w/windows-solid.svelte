<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/encrm8bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="encrm8bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:windows-solid" {...props}></Icon>
