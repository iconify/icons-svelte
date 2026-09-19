<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u13qa-evs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u13qa-evs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:signal" {...props}></Icon>
