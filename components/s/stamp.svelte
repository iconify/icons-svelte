<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rah3vs0hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="rah3vs0hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:stamp" {...props}></Icon>
