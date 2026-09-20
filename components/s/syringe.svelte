<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hksa8qn3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hksa8qn3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:syringe" {...props}></Icon>
