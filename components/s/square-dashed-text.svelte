<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkqbgz0qe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xkqbgz0qe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-dashed-text" {...props}></Icon>
