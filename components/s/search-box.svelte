<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpe_zkb5e.css';
import '../../css/h/heok19bbn.css';
import '../../css/c/cz1u-qu3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpe_zkb5e"/><path class="heok19bbn"/><path class="cz1u-qu3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:search-box" {...props}></Icon>
