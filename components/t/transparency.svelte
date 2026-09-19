<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0fap9byy.css';
import '../../css/e/eax3dpvsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0fap9byy"/><path class="eax3dpvsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:transparency" {...props}></Icon>
