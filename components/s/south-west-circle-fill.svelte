<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3pdm5vqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3pdm5vqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:south-west-circle-fill" {...props}></Icon>
