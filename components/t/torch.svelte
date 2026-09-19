<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mavdskbnx.css';
import '../../css/d/dke65eb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mavdskbnx"/><path class="dke65eb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:torch" {...props}></Icon>
