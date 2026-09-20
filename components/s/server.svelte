<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9xgz4b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9xgz4b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:server" {...props}></Icon>
