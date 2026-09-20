<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6k1q-bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6k1q-bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:vector-logo-zone" {...props}></Icon>
