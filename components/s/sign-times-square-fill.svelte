<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0nbbgb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0nbbgb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-times-square-fill" {...props}></Icon>
