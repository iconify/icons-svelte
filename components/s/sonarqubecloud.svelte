<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coc-1sbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coc-1sbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sonarqubecloud" {...props}></Icon>
