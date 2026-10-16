<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osf7zog9q.css';
import '../../css/h/h818ewufo.css';
import '../../css/k/krsiqfbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="osf7zog9q"/><path class="h818ewufo"/><path class="krsiqfbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tokamak-48-bold" {...props}></Icon>
