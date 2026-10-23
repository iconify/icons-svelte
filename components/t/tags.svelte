<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxx7ztbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxx7ztbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tags" {...props}></Icon>
