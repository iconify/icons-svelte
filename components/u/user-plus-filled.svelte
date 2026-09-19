<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp_4tvblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp_4tvblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:user-plus-filled" {...props}></Icon>
