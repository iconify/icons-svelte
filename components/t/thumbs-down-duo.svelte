<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw8xrvjbq.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ouxafviye.css';
import '../../css/l/l-21uxusr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rw8xrvjbq secondary"/><g class="dt0cm9dhy primary"><path class="ouxafviye"/><path class="l-21uxusr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:thumbs-down-duo" {...props}></Icon>
