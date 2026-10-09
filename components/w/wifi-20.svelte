<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-3px956v.css';
import '../../css/x/x5abyccpj.css';
import '../../css/z/z05xz87_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g-3px956v"/><path class="x5abyccpj"/><path class="z05xz87_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-20" {...props}></Icon>
