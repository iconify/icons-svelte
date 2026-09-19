<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tngcb0q4r.css';
import '../../css/k/kkdqyclyg.css';
import '../../css/o/or3-8lbcy.css';
import '../../css/b/bld59mbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tngcb0q4r"/><path class="kkdqyclyg"/><path class="or3-8lbcy"/><path class="bld59mbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:school-bell-02" {...props}></Icon>
