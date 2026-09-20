<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siwd_6bfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="siwd_6bfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:settings-input-antenna" {...props}></Icon>
