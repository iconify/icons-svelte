<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-fsf2rdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-fsf2rdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-align-offset-bottom-fill" {...props}></Icon>
