<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh0qq1b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vh0qq1b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:taipei101-fill" {...props}></Icon>
