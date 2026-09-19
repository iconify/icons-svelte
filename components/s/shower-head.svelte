<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk93phdge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk93phdge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:shower-head" {...props}></Icon>
