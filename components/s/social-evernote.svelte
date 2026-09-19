<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmmcidcze.css';
import '../../css/t/tba5rlbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qmmcidcze"/><path class="tba5rlbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-evernote" {...props}></Icon>
