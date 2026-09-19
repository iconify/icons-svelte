<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t3_l9ubrw.css';
import '../../css/b/b0caljujn.css';
import '../../css/b/br6u71brj.css';
import '../../css/o/ons53cb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t3_l9ubrw"/><path class="b0caljujn"/><path class="br6u71brj"/><circle class="ons53cb4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:soda-can" {...props}></Icon>
