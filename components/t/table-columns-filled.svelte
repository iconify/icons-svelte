<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b05i6cbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b05i6cbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-columns-filled" {...props}></Icon>
