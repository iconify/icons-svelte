<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5u5voitv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5u5voitv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timer-alert-outline" {...props}></Icon>
