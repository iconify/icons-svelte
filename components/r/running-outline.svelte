<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7y83cc-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7y83cc-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-outline" {...props}></Icon>
