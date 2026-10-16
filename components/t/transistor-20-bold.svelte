<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6lsc2brm.css';
import '../../css/u/uykl-2-4c.css';
import '../../css/m/mlich4fig.css';
import '../../css/n/ntp17abmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o6lsc2brm"/><path class="uykl-2-4c"/><path class="mlich4fig"/><path class="ntp17abmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:transistor-20-bold" {...props}></Icon>
