<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0rf3fb-u.css';
import '../../css/s/s_gjiybtk.css';
import '../../css/v/v3cog_bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o0rf3fb-u"/><path class="s_gjiybtk"/><path class="v3cog_bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wind-direction-48" {...props}></Icon>
