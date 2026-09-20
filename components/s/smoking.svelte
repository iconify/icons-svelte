<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhihigb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhihigb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:smoking" {...props}></Icon>
