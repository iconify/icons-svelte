<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itz8c4-rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itz8c4-rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:s7airlines" {...props}></Icon>
