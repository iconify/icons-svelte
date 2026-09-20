<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfr8q1bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfr8q1bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wakatime" {...props}></Icon>
