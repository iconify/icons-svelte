<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1fd39d2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="e1fd39d2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:trigger" {...props}></Icon>
