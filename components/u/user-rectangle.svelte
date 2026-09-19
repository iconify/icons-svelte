<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk5sbi9lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk5sbi9lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:user-rectangle" {...props}></Icon>
