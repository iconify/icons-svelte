<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqn0bub3s.css';
import '../../css/l/l44l4kkdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqn0bub3s"/><path clip-rule="evenodd" class="l44l4kkdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:storm-fill" {...props}></Icon>
