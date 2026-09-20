<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7ejmibhb.css';
import '../../css/z/z6i6gousf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7ejmibhb"/><path class="z6i6gousf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:video" {...props}></Icon>
