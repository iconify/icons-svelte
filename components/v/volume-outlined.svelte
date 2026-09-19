<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdwbaegjf.css';
import '../../css/g/g8gex4kkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdwbaegjf"/><path class="g8gex4kkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:volume-outlined" {...props}></Icon>
