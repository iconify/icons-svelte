<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/z/z08-9pbuq.css';
import '../../css/z/z3cyn9bdw.css';
import '../../css/s/st6veybqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z08-9pbuq"/><path class="z3cyn9bdw"/><path class="st6veybqt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:users-round" {...props}></Icon>
