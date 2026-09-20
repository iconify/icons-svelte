<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g21besblw.css';
import '../../css/f/fm77d8b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g21besblw"/><path class="fm77d8b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vix" {...props}></Icon>
