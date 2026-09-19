<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzc_s3b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzc_s3b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:thermometer" {...props}></Icon>
