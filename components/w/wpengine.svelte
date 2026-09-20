<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg7qg7bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg7qg7bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wpengine" {...props}></Icon>
