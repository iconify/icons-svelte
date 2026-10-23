<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao2o_1coz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao2o_1coz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:skip-back" {...props}></Icon>
