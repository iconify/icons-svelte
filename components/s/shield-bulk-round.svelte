<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npgb128ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npgb128ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-bulk-round" {...props}></Icon>
