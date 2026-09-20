<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i96mgiblb.css';
import '../../css/u/uj6e1ab-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":140.625,"height":140.625};
const content = `<path class="i96mgiblb"/><path class="uj6e1ab-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:vagrant" {...props}></Icon>
