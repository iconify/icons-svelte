<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo_j2ivdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wo_j2ivdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tailwind-outline" {...props}></Icon>
