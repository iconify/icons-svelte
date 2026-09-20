<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0hexbc2j.css';
import '../../css/h/h447xtb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="o0hexbc2j"/><path class="h447xtb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:traccar" {...props}></Icon>
