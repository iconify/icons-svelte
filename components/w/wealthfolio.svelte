<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0nm-3j1m.css';
import '../../css/o/o4qm4qbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="v0nm-3j1m"/><path class="o4qm4qbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wealthfolio" {...props}></Icon>
