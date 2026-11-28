<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olhb174op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olhb174op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shuffle-sparkles-solid" {...props}></Icon>
