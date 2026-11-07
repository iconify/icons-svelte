<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtmuzrg2o.css';
import '../../css/t/t9ntucclw.css';
import '../../css/v/v81dzmbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtmuzrg2o"/><path clip-rule="evenodd" class="t9ntucclw"/><path class="v81dzmbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:safe-circle-bold-duotone" {...props}></Icon>
