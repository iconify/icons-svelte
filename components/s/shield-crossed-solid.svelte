<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e11jas_xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e11jas_xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-crossed-solid" {...props}></Icon>
