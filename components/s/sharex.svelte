<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2xqc7bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2xqc7bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sharex" {...props}></Icon>
