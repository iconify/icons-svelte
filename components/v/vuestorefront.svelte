<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8nfwjaam.css';
import '../../css/v/vgzcqeb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k8nfwjaam"/><path class="vgzcqeb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:vuestorefront" {...props}></Icon>
