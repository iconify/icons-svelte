<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bujcfabcl.css';
import '../../css/p/p68_n_bch.css';
import '../../css/r/riwp_rwvj.css';
import '../../css/u/u04jombws.css';
import '../../css/x/x5rsn2cfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bujcfabcl"/><path class="p68_n_bch"/><path class="riwp_rwvj"/><path class="u04jombws"/><path class="x5rsn2cfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:unity-wordmark" {...props}></Icon>
