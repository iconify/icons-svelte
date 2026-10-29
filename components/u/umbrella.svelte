<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7gfubdlt.css';
import '../../css/l/lrkjd1bsy.css';
import '../../css/l/lriab0bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7gfubdlt wm-a"/><path class="lrkjd1bsy wm-k"/><path class="lriab0bfg wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:umbrella" {...props}></Icon>
