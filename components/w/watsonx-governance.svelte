<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilbhp-bhd.css';
import '../../css/j/jzrd8fxam.css';
import '../../css/u/uw8ydqbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ilbhp-bhd"/><path class="jzrd8fxam"/><path class="uw8ydqbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:watsonx-governance" {...props}></Icon>
