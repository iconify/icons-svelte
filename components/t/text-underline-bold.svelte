<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eipxycc0p.css';
import '../../css/l/lvp3cpbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eipxycc0p"/><path class="lvp3cpbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-underline-bold" {...props}></Icon>
