<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gg84aebsp.css';
import '../../css/y/y481nlytz.css';
import '../../css/u/um_27sbup.css';
import '../../css/j/jnepjhbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gg84aebsp"/><path class="y481nlytz"/><circle class="um_27sbup"/><path class="jnepjhbrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:station-broken" {...props}></Icon>
