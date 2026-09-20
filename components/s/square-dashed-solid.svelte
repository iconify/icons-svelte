<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua4zgpq_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua4zgpq_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:square-dashed-solid" {...props}></Icon>
