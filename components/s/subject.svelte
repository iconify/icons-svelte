<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnae_cc0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnae_cc0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:subject" {...props}></Icon>
