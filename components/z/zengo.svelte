<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmb706_bp.css';
import '../../css/j/j3ziv3b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmb706_bp"/><path class="j3ziv3b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zengo" {...props}></Icon>
