<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo30i31yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo30i31yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:zap-off-solid" {...props}></Icon>
