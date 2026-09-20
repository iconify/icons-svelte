<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evfd4hbar.css';
import '../../css/l/lt9r55aoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evfd4hbar"/><path class="lt9r55aoa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:startups" {...props}></Icon>
