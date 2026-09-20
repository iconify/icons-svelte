<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai6wcvbfj.css';
import '../../css/f/fhh8osb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ai6wcvbfj"/><path class="fhh8osb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:users-solid" {...props}></Icon>
