<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot_58-5rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot_58-5rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:text-paragraph" {...props}></Icon>
