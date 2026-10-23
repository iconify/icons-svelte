<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jci9iccjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jci9iccjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:unlink" {...props}></Icon>
