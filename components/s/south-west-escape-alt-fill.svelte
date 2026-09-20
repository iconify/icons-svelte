<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6wlk20vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6wlk20vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-west-escape-alt-fill" {...props}></Icon>
