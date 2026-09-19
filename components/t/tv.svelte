<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_n7y0bah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m_n7y0bah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:tv" {...props}></Icon>
