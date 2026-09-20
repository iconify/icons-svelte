<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxnfvbayz.css';
import '../../css/h/h46e1ybha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxnfvbayz"/><path class="h46e1ybha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:watch-beat-1" {...props}></Icon>
