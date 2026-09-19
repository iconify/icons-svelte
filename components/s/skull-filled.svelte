<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjd_78iqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjd_78iqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skull-filled" {...props}></Icon>
