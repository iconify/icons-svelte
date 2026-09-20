<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3cd7ibxu.css';
import '../../css/p/pz9k4djmg.css';
import '../../css/v/v9x3yzuus.css';
import '../../css/q/qipz36fvw.css';
import '../../css/e/e555xqbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m3cd7ibxu"/><path class="pz9k4djmg"/><path class="v9x3yzuus"/><path class="qipz36fvw"/><path class="e555xqbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-emojis:sparkling-heart" {...props}></Icon>
