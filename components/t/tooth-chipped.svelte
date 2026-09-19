<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7rpwe7vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l7rpwe7vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-chipped" {...props}></Icon>
