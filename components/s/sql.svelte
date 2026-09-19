<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2nh5t9ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2nh5t9ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sql" {...props}></Icon>
