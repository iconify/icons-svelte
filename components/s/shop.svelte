<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au7sa78qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="au7sa78qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shop" {...props}></Icon>
