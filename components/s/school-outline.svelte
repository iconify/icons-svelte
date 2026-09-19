<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s12qakbkj.css';
import '../../css/q/q6hvgntet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s12qakbkj"/><path class="q6hvgntet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:school-outline" {...props}></Icon>
