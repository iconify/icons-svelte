<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyyrubtqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyyrubtqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-case-lowercase" {...props}></Icon>
