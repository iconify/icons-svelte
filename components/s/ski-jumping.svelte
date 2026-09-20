<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emfpa0b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="emfpa0b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:ski-jumping" {...props}></Icon>
