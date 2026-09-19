<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy1i_6bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dy1i_6bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:thumbs-up-fill" {...props}></Icon>
