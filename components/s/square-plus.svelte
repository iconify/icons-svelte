<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqq7tyroa.css';
import '../../css/a/a-8u3piaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqq7tyroa wm-k"/><path class="a-8u3piaa wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:square-plus" {...props}></Icon>
