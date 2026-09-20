<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbbvttb9i.css';
import '../../css/w/we1tctbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbbvttb9i"/><path class="we1tctbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:stackoverflow" {...props}></Icon>
