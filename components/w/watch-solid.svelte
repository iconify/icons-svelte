<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udqx-wbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udqx-wbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:watch-solid" {...props}></Icon>
