<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my_0eb8dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my_0eb8dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:school-filled" {...props}></Icon>
