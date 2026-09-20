<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi4z6zb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mi4z6zb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:shield-plus-solid" {...props}></Icon>
