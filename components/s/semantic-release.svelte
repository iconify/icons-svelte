<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq8qvx7lw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="uq8qvx7lw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:semantic-release" {...props}></Icon>
