<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op_ar-b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="op_ar-b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:table-export" {...props}></Icon>
