<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc9gyxref.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mc9gyxref"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wish" {...props}></Icon>
