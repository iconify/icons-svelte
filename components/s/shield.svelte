<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye9gr2dqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="ye9gr2dqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:shield" {...props}></Icon>
