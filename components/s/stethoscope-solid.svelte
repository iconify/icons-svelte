<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esq-ijbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esq-ijbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:stethoscope-solid" {...props}></Icon>
