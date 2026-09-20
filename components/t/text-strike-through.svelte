<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo_f4rbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oo_f4rbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:text-strike-through" {...props}></Icon>
