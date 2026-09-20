<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpqq-ve2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpqq-ve2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:wheelchair-solid" {...props}></Icon>
