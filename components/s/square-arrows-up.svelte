<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8tvufbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8tvufbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrows-up" {...props}></Icon>
