<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg1m4vb6k.css';
import '../../css/o/ovova4bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wg1m4vb6k"/><path class="ovova4bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:thunderstorm-scattered-night" {...props}></Icon>
