<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmeuqkb-h.css';
import '../../css/h/hp4dggb8v.css';
import '../../css/d/dzdrvzb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qmeuqkb-h"/><path class="hp4dggb8v"/><path class="dzdrvzb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trophy-48" {...props}></Icon>
