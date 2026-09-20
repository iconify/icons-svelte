<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeduddcik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeduddcik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:step-forward-alt" {...props}></Icon>
