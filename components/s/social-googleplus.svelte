<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3f2lt1bs.css';
import '../../css/x/x720oqwne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u3f2lt1bs"/><path class="x720oqwne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-googleplus" {...props}></Icon>
