<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3qvylb2e.css';
import '../../css/e/e1u7ewaaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="s3qvylb2e"/><path class="e1u7ewaaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:walk" {...props}></Icon>
