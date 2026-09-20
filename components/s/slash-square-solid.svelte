<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1l7e8acw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1l7e8acw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:slash-square-solid" {...props}></Icon>
