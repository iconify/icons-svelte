<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adi79t1qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adi79t1qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sort" {...props}></Icon>
