<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu1ylgbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu1ylgbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:thermometer" {...props}></Icon>
