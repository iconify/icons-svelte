<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up8_hjm1g.css';
import '../../css/k/k_6prvftm.css';
import '../../css/q/qljqqy97f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="up8_hjm1g"/><path class="k_6prvftm"/><path class="qljqqy97f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whisk-48" {...props}></Icon>
