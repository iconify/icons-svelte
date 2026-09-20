<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auh_ykphj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auh_ykphj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vuetify" {...props}></Icon>
